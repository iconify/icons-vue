<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlv8u-u-t.css';
import '../../css/a/aso8_oe6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="xlv8u-u-t"/><path class="aso8_oe6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:alert-filled" /></template>

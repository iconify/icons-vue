<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtcxehb-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtcxehb-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:citrus-solid" /></template>

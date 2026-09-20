<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj65r2bip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj65r2bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:analysis" /></template>

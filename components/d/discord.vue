<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8d4mwbzs.css';
import '../../css/m/ml8_8mbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8d4mwbzs"/><path class="ml8_8mbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:discord" /></template>

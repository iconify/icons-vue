<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/douh-p_jc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="douh-p_jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:file-circle-question" /></template>

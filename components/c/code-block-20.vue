<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co0vf9bvy.css';
import '../../css/a/ao9i_zcjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="co0vf9bvy"/><path class="ao9i_zcjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:code-block-20" /></template>

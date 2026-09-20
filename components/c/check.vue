<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-3506bll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-3506bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:check" /></template>

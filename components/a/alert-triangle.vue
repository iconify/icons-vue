<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jas9_-b0f.css';
import '../../css/h/hf3ru2_zl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer jas9_-b0f"/><path class="duoicon-primary-layer hf3ru2_zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:alert-triangle" /></template>

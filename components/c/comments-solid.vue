<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw-d8obrx.css';
import '../../css/z/zh8kziv_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw-d8obrx"/><path class="zh8kziv_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:comments-solid" /></template>

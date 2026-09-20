<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2o9d7xpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2o9d7xpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-yaml" /></template>

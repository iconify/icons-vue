<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqx9h12wb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqx9h12wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-pull-request-close-fill" /></template>

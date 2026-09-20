<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi_s3db9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vi_s3db9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:church-fill" /></template>

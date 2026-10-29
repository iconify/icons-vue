<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3sn4wb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3sn4wb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ban-solid" /></template>

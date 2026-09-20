<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-pem9bhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-pem9bhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alphabet-f-circle-outline" /></template>

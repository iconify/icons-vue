<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3vi22b5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3vi22b5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-convert-outline" /></template>

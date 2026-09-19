<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyzqvq11k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyzqvq11k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrow-circle-down" /></template>

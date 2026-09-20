<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdzlzlb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdzlzlb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:image-outline" /></template>

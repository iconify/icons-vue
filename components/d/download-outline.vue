<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml90et9yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ml90et9yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:download-outline" /></template>

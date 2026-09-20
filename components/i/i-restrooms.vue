<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0sarzx0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="h0sarzx0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-restrooms" /></template>

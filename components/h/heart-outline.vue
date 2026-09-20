<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7rvp3y7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m7rvp3y7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:heart-outline" /></template>

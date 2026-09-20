<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx9bq6bdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rx9bq6bdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:headphone" /></template>

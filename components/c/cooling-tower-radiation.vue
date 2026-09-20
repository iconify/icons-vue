<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u85ln7bqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u85ln7bqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:cooling-tower-radiation" /></template>

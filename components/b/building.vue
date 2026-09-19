<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpwaw1qia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zpwaw1qia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:building" /></template>

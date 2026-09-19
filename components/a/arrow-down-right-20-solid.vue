<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juh-xlr9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="juh-xlr9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-down-right-20-solid" /></template>

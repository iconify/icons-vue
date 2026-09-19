<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sky5aebku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sky5aebku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:arrow-up-alt2" /></template>

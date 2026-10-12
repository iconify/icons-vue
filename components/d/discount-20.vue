<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmd-u84-k.css';
import '../../css/h/h9ysk2g4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gmd-u84-k"/><path class="h9ysk2g4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:discount-20" /></template>

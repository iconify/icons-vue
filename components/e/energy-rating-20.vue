<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/geb7k3hdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="geb7k3hdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-rating-20" /></template>

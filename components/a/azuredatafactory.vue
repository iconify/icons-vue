<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc96p9j4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bc96p9j4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:azuredatafactory" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgdbr_pqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="hgdbr_pqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:expand" /></template>

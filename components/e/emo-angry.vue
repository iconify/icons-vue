<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb5d9ngtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="eb5d9ngtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:emo-angry" /></template>

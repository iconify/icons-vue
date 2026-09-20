<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km1sp5-1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="km1sp5-1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:jerrican" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny9tj592h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ny9tj592h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:facebook-alt" /></template>

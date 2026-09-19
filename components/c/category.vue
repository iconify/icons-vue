<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk6sm91fr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hk6sm91fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:category" /></template>

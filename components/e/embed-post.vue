<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg3a_acxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mg3a_acxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:embed-post" /></template>

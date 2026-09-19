<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2yaomj3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a2yaomj3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:html" /></template>

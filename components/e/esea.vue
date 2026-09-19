<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgwhpuu7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bgwhpuu7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:esea" /></template>

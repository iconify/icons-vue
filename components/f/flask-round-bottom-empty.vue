<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knxbbqb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="knxbbqb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:flask-round-bottom-empty" /></template>

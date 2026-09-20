<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf7y1jtyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="sf7y1jtyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:division" /></template>

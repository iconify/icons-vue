<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkec0kb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fkec0kb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:badge" /></template>

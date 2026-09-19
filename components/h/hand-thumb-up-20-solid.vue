<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtrpkvbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gtrpkvbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:hand-thumb-up-20-solid" /></template>

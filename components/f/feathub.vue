<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pejrbtb3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pejrbtb3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:feathub" /></template>

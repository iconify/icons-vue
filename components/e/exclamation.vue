<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlubp1u1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":1408};
const content = `<path class="wlubp1u1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:exclamation" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhdau5_nb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="dhdau5_nb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:font-awesome-alt" /></template>

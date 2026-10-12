<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ultpy5svx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ultpy5svx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:logo-linkedin-20" /></template>

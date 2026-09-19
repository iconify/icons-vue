<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnlyh2k5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="cnlyh2k5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:lock" /></template>

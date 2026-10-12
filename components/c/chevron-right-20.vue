<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwuut5b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mwuut5b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-right-20" /></template>

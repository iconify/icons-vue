<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkij0r87r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mkij0r87r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:function-add" /></template>

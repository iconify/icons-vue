<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci9979btv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="ci9979btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:accounts-outline" /></template>

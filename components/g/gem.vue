<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke5kq2yfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="ke5kq2yfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:gem" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0j1o-b1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="k0j1o-b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:f-cursive-circle-fill" /></template>

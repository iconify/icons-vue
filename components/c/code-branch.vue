<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kplpru4sq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="kplpru4sq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:code-branch" /></template>

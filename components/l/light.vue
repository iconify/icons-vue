<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djj8e4c7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":688,"height":717};
const content = `<path class="djj8e4c7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:light" /></template>

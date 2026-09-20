<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5xg36kjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="k5xg36kjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:check" /></template>

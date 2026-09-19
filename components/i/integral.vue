<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6f823bxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="l6f823bxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:integral" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8kaj0xhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":416,"height":512};
const content = `<path class="h8kaj0xhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:flutter" /></template>

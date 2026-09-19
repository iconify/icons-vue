<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwkfvmbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":444,"height":512};
const content = `<path class="cwkfvmbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:gitpod" /></template>

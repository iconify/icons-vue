<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7el0acfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d7el0acfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:fabfile" /></template>

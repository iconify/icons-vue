<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av5liu7sk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":428,"height":512};
const content = `<path class="av5liu7sk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:bloc" /></template>

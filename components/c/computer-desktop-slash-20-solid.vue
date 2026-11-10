<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co8pgjoyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="co8pgjoyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:computer-desktop-slash-20-solid" /></template>

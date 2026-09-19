<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4e7s067m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a4e7s067m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:folder" /></template>

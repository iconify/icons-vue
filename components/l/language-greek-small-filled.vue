<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxo_xnd6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="wxo_xnd6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:language-greek-small-filled" /></template>

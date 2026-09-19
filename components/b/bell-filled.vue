<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2mb6lbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="h2mb6lbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:bell-filled" /></template>

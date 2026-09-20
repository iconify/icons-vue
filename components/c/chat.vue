<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok-_jky8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ok-_jky8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:chat" /></template>

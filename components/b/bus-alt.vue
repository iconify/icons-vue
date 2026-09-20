<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he1sdb3fh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="he1sdb3fh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:bus-alt" /></template>

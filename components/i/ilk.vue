<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4xau874c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p4xau874c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ilk" /></template>

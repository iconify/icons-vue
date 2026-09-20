<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc42u29hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tc42u29hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hockey-puck" /></template>

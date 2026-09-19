<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcw18056q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="pcw18056q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:ftpsession" /></template>

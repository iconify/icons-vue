<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8md0slze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="w8md0slze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hashtag" /></template>

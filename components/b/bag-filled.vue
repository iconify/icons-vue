<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmixd20za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zmixd20za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bag-filled" /></template>

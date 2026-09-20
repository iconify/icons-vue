<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r29ui0i8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r29ui0i8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:crop2" /></template>

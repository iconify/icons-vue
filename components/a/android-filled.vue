<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0b4gnb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0b4gnb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:android-filled" /></template>

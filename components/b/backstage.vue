<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3kng8m4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3kng8m4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:backstage" /></template>

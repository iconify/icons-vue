<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csz6thblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csz6thblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bell-minus" /></template>

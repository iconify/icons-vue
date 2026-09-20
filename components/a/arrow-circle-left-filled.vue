<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rht-jrsfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rht-jrsfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-circle-left-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcor0c4fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcor0c4fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:book-alt-filled" /></template>

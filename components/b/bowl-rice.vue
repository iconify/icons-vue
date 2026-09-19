<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7i1l88xv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7i1l88xv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bowl-rice" /></template>

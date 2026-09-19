<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i48xvju3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="i48xvju3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:less-than" /></template>

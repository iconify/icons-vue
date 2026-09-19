<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cefb5cckj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cefb5cckj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:github-with-circle" /></template>

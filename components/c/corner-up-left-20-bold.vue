<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs5ldor7z.css';
import '../../css/i/ins2hsbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cs5ldor7z"/><path class="ins2hsbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-up-left-20-bold" /></template>

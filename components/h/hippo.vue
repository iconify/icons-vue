<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui36x6bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="ui36x6bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hippo" /></template>

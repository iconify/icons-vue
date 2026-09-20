<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usl3xqbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="usl3xqbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:clap-16" /></template>

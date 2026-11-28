<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvjfn3lzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvjfn3lzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bookmarks-solid" /></template>

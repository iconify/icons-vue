<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbu2i64xd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zbu2i64xd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:haxe" /></template>

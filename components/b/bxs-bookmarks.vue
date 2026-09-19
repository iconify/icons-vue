<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4hvibczh.css';
import '../../css/p/p-3uqobhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4hvibczh"/><path class="p-3uqobhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-bookmarks" /></template>

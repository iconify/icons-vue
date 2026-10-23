<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5tg_i0yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5tg_i0yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:banknote-x" /></template>

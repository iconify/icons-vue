<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3u1wjb0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c3u1wjb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:clipboard-list-filled" /></template>

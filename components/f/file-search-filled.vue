<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3nlvcvue.css';
import '../../css/l/llokiq9ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3nlvcvue"/><path class="llokiq9ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:file-search-filled" /></template>

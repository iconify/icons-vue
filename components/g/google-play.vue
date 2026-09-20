<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa6m-3b-n.css';
import '../../css/t/tszhuobqh.css';
import '../../css/z/zjx5z9b7a.css';
import '../../css/r/rzgmi4b0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xa6m-3b-n"/><path class="tszhuobqh"/><path class="zjx5z9b7a"/><path class="rzgmi4b0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:google-play" /></template>

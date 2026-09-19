<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uot15gzqk.css';
import '../../css/n/nf2tmmxki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uot15gzqk"/><path class="nf2tmmxki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dropdown" /></template>

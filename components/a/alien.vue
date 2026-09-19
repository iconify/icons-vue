<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3uu5lbtk.css';
import '../../css/o/omkgw9bsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3uu5lbtk"/><path class="omkgw9bsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:alien" /></template>

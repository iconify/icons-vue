<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osp4wzbqk.css';
import '../../css/u/uotgxeb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osp4wzbqk"/><path class="uotgxeb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-download" /></template>

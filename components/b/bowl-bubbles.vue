<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr-hoeb6g.css';
import '../../css/u/u8hb6sbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b zr-hoeb6g"/><path class="b u8hb6sbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bowl-bubbles" /></template>

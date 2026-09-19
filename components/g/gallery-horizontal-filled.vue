<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oia2jebxk.css';
import '../../css/e/emuklcgdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="oia2jebxk"/><path class="emuklcgdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:gallery-horizontal-filled" /></template>

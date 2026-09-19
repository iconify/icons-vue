<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtvcw1bvs.css';
import '../../css/f/f5u8_gz6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtvcw1bvs"/><path class="f5u8_gz6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:graduation" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3-nd4bnk.css';
import '../../css/b/bwibdw4bb.css';
import '../../css/f/fiavfxncv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3-nd4bnk"/><path class="bwibdw4bb"/><path class="fiavfxncv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:equal-circle" /></template>

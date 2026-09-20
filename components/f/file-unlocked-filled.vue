<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgf_iypbv.css';
import '../../css/n/n662dbbwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgf_iypbv"/><path class="n662dbbwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-unlocked-filled" /></template>

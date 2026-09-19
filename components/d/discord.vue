<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srdcyza2r.css';
import '../../css/g/g7n3rd2ag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srdcyza2r"/><path class="g7n3rd2ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:discord" /></template>

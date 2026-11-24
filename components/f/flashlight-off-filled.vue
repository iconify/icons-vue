<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gotpsbcpu.css';
import '../../css/w/wxtz8objy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gotpsbcpu"/><path class="wxtz8objy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:flashlight-off-filled" /></template>

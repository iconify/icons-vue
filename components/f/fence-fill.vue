<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgkem10bk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgkem10bk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fence-fill" /></template>

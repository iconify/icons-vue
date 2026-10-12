<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0wlds3qh.css';
import '../../css/u/uz8c7kbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0wlds3qh"/><path clip-rule="evenodd" class="uz8c7kbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bug-play-filled" /></template>

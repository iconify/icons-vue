<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8xrq0a2p.css';
import '../../css/d/d-jaw6bew.css';
import '../../css/q/q3wy11brx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8xrq0a2p"/><path class="d-jaw6bew"/><path class="q3wy11brx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-archive-filled" /></template>

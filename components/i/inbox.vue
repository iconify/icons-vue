<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvh9a2pzk.css';
import '../../css/h/hgwnlybsl.css';
import '../../css/e/e_2p_w-co.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvh9a2pzk"/><path class="hgwnlybsl"/><path class="e_2p_w-co"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:inbox" /></template>

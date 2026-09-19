<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryv3btb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryv3btb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:files" /></template>

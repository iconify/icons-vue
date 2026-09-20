<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nma_pbbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nma_pbbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:chat-bubble-oval-smiley-1-remix" /></template>

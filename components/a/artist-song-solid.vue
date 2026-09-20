<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6skg3cyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p6skg3cyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:artist-song-solid" /></template>

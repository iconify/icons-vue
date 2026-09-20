<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl7y-9koh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dl7y-9koh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:add-layer-2-solid" /></template>

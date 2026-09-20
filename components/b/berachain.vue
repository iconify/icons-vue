<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drfbo4b6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drfbo4b6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:berachain" /></template>

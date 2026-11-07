<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5zd-yeve.css';
import '../../css/i/i5wpqgyez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5zd-yeve"/><path clip-rule="evenodd" class="i5wpqgyez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:key-minimalistic-square-bold" /></template>

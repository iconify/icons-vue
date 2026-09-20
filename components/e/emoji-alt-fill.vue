<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgf6tkv2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qgf6tkv2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:emoji-alt-fill" /></template>

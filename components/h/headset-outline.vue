<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/defuaabko.css';
import '../../css/n/n43_i1bug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="defuaabko"/><path clip-rule="evenodd" class="n43_i1bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:headset-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4_xldbbg.css';
import '../../css/z/zlbz5jbgm.css';
import '../../css/z/zhg6ptbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b4_xldbbg"/><path clip-rule="evenodd" class="zlbz5jbgm"/><path clip-rule="evenodd" class="zhg6ptbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dry-fill" /></template>

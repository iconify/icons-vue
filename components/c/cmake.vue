<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiyi5t_0v.css';
import '../../css/u/ufh9qkbxk.css';
import '../../css/n/naagimbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oiyi5t_0v"/><path class="ufh9qkbxk"/><path class="naagimbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:cmake" /></template>

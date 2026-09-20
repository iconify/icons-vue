<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1ibgbpxi.css';
import '../../css/z/zvg05gx_g.css';
import '../../css/d/d4-m_ebkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1ibgbpxi"/><path class="zvg05gx_g"/><path class="d4-m_ebkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:hipchat" /></template>

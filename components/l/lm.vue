<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-3lhcbzm.css';
import '../../css/k/kvngqrmke.css';
import '../../css/s/s_i4p2bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-3lhcbzm"/><path class="kvngqrmke"/><path class="s_i4p2bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lm" /></template>

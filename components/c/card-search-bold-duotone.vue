<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj3u4_bby.css';
import '../../css/k/kdqg7zpqi.css';
import '../../css/y/yb1t-pwor.css';
import '../../css/s/s6qd-zbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj3u4_bby"/><path clip-rule="evenodd" class="kdqg7zpqi"/><path class="yb1t-pwor"/><path class="s6qd-zbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:card-search-bold-duotone" /></template>

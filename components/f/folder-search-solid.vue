<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klk01p-xy.css';
import '../../css/l/lsqc0acbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klk01p-xy"/><path clip-rule="evenodd" class="lsqc0acbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:folder-search-solid" /></template>

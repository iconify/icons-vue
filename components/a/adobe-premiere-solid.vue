<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u06tkfbua.css';
import '../../css/k/ktvtx3m1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u06tkfbua"/><path clip-rule="evenodd" class="ktvtx3m1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:adobe-premiere-solid" /></template>

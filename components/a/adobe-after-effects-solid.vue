<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv4m5hauv.css';
import '../../css/t/tma0dchkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv4m5hauv"/><path clip-rule="evenodd" class="tma0dchkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:adobe-after-effects-solid" /></template>

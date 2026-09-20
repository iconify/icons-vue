<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wak7u4bkm.css';
import '../../css/u/uybk_4bpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wak7u4bkm"/><path class="uybk_4bpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:figma-line" /></template>

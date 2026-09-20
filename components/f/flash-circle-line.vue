<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti42iobpp.css';
import '../../css/w/w3z640blx.css';
import '../../css/b/b_fzd2v5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti42iobpp"/><path class="w3z640blx"/><path class="b_fzd2v5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flash-circle-line" /></template>

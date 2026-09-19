<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9_tcobxs.css';
import '../../css/t/t_qou-ite.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9_tcobxs"/><path class="t_qou-ite"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-bookmark-alt-minus" /></template>

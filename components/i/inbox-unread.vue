<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq2qa5b_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lq2qa5b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:inbox-unread" /></template>

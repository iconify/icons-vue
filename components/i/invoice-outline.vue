<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7bk8s24b.css';
import '../../css/c/cnc3b_b8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7bk8s24b"/><path clip-rule="evenodd" class="cnc3b_b8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:invoice-outline" /></template>

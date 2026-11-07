<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfz6qsjee.css';
import '../../css/c/cq_7-dbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfz6qsjee"/><path clip-rule="evenodd" class="cq_7-dbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-arrow-bold-duotone" /></template>

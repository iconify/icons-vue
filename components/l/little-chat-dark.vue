<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9-4b0rca.css';
import '../../css/l/lrv75jbqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b9-4b0rca"/><path class="lrv75jbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:little-chat-dark" /></template>

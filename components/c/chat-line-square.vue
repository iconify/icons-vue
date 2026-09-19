<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkpxsvb_g.css';
import '../../css/o/ot6g9xx6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gkpxsvb_g"/><path class="ot6g9xx6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:chat-line-square" /></template>

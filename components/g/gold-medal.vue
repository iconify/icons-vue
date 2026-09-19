<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iojc3c5mq.css';
import '../../css/h/h-mv3pyqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="iojc3c5mq"/><path class="h-mv3pyqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:gold-medal" /></template>

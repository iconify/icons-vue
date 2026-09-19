<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxl51xg6q.css';
import '../../css/e/eruok2ino.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer yxl51xg6q"/><path class="duoicon-primary-layer eruok2ino"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:book-2" /></template>

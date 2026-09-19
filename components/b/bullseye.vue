<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh4riuv9c.css';
import '../../css/c/cw8brcc2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zh4riuv9c"/><path class="cw8brcc2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:bullseye" /></template>

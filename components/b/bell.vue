<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezbfhcbuu.css';
import '../../css/a/a45l8jhyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer ezbfhcbuu"/><path class="a45l8jhyb duoicon-secondary-layer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:bell" /></template>

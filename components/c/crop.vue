<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh14zko1u.css';
import '../../css/u/uouny_b5s.css';
import '../../css/p/pnj4t1rqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh14zko1u"/><path class="uouny_b5s"/><path class="pnj4t1rqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:crop" /></template>

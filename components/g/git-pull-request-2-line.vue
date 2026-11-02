<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pshkky4_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pshkky4_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-pull-request-2-line" /></template>

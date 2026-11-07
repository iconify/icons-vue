<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i45zppjnu.css';
import '../../css/u/u4oiq_b1p.css';
import '../../css/y/yil3q6l6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i45zppjnu"/><path clip-rule="evenodd" class="u4oiq_b1p"/><path class="yil3q6l6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-bold-duotone" /></template>

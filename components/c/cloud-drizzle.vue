<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxmh1e_dh.css';
import '../../css/n/np-r86b3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxmh1e_dh"/><path class="np-r86b3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:cloud-drizzle" /></template>

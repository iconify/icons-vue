<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgwhj2-nq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bgwhj2-nq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:history-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8o7esb0b.css';
import '../../css/l/lkctm_bgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8o7esb0b"/><path clip-rule="evenodd" class="lkctm_bgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:egg-fried-filled" /></template>

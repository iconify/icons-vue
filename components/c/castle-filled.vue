<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw-8xobrx.css';
import '../../css/o/ozytg_30r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uw-8xobrx"/><path class="ozytg_30r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:castle-filled" /></template>

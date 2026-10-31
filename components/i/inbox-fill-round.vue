<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb8xb_bsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb8xb_bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:inbox-fill-round" /></template>

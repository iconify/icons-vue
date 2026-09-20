<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmci96b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lmci96b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:backpack" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swv0urbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="swv0urbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brightness-fill" /></template>

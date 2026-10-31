<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plreceblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plreceblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:biohazard-round" /></template>

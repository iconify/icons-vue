<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk9yzt_fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zk9yzt_fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:face-neutral-fill-round" /></template>

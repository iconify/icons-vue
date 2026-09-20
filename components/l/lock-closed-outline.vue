<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byz9vkb6r.css';
import '../../css/h/h_ma9rt0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="byz9vkb6r"/><path class="h_ma9rt0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:lock-closed-outline" /></template>

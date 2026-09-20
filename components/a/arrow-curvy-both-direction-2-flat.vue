<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxgi8ob_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wxgi8ob_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:arrow-curvy-both-direction-2-flat" /></template>

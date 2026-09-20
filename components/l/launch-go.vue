<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwraok8xf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwraok8xf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:launch-go" /></template>

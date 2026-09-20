<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlqn90vhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wlqn90vhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:insert-row-remix" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbk7imy3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mbk7imy3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:bell-set-timer-remix" /></template>

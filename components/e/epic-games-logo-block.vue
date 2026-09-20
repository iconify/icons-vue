<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjte8zblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mjte8zblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:epic-games-logo-block" /></template>

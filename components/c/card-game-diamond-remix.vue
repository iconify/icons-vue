<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzkv1krsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dzkv1krsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:card-game-diamond-remix" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnv1cu90a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vnv1cu90a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:layout-window-25-remix" /></template>

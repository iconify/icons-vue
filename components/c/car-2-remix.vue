<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2hth9biw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c2hth9biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:car-2-remix" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbnmd3bgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kbnmd3bgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:hierarchy-2-remix" /></template>

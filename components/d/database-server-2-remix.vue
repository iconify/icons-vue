<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhy5ambjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qhy5ambjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:database-server-2-remix" /></template>

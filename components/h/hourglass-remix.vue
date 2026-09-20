<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv1bq6mjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qv1bq6mjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:hourglass-remix" /></template>

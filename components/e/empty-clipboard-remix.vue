<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyl9-3bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iyl9-3bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:empty-clipboard-remix" /></template>

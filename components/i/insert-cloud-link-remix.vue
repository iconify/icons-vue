<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txkmch_5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="txkmch_5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:insert-cloud-link-remix" /></template>

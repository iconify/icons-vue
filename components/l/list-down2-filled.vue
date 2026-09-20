<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm1w6yb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vm1w6yb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:list-down2-filled" /></template>

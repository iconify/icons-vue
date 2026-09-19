<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngywqob2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ngywqob2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:bluetooth-outline" /></template>

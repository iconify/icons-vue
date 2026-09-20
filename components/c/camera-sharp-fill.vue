<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uon1petdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uon1petdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:camera-sharp-fill" /></template>

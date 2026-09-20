<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akoiidbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="akoiidbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:hand-washing-solid" /></template>

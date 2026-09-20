<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6-cancaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o6-cancaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:bullet-list-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkqy2hbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xkqy2hbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:information-circle-solid" /></template>

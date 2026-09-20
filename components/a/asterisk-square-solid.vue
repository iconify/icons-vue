<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlpzi9wwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rlpzi9wwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:asterisk-square-solid" /></template>

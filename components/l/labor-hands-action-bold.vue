<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emu7ok8id.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="emu7ok8id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:labor-hands-action-bold" /></template>

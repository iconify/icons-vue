<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vurxy5g5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vurxy5g5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:dart-logo-solid" /></template>

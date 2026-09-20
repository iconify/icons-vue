<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtpce1bsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dtpce1bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:command-button-keyboard-bold" /></template>

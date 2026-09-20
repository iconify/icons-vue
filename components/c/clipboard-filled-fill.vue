<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2pmeaj-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r2pmeaj-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:clipboard-filled-fill" /></template>

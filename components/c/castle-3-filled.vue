<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chmdl0b7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chmdl0b7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:castle-3-filled" /></template>

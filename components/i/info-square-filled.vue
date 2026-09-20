<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnenm3buo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xnenm3buo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:info-square-filled" /></template>

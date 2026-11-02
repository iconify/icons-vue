<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx9vchbxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fx9vchbxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bricks-fill" /></template>

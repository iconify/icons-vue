<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj1abhbxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hj1abhbxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:diskette-outline" /></template>

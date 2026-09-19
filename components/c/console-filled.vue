<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hck2hdcpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hck2hdcpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:console-filled" /></template>

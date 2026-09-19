<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr66j6b6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qr66j6b6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:battery-vertical-full" /></template>

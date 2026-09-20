<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znw3c4lsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="znw3c4lsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:card-receive" /></template>

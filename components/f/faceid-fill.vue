<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk_fm6bvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pk_fm6bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:faceid-fill" /></template>

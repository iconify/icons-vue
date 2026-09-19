<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh2htabni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oh2htabni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:club" /></template>

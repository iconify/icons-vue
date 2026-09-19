<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xugc58bbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xugc58bbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:italic" /></template>

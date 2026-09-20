<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqh28jm6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqh28jm6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:fork-knife" /></template>

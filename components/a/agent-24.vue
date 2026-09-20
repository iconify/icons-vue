<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv0mdubqx.css';
import '../../css/q/qgpj5zbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv0mdubqx"/><path class="qgpj5zbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:agent-24" /></template>

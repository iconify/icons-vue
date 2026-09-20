<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdagnjbde.css';
import '../../css/w/wjgo_ebim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdagnjbde"/><path class="wjgo_ebim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:cog" /></template>

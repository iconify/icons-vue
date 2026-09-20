<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8xv77byg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8xv77byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:direct-up-filled" /></template>

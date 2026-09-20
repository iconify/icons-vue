<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9m0gbckt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9m0gbckt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:layers-filled" /></template>

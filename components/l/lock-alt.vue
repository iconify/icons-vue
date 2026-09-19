<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/piif4cchw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="piif4cchw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:lock-alt" /></template>

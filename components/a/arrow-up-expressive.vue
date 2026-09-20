<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu6ptwbdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu6ptwbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrow-up-expressive" /></template>

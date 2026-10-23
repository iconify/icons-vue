<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z12zi2w1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z12zi2w1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:dice-6" /></template>

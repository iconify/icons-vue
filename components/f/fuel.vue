<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd2umnbdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd2umnbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:fuel" /></template>

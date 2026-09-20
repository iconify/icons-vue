<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygz1y6bnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygz1y6bnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:headset-off-sharp" /></template>

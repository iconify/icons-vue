<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_nu60t3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_nu60t3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bitcoin-duotone" /></template>

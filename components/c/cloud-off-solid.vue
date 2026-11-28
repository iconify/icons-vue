<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk97fbb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kk97fbb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloud-off-solid" /></template>

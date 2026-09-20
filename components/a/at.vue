<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcy8yybqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcy8yybqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:at" /></template>

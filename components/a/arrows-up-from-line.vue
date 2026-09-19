<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3m55ehci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3m55ehci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:arrows-up-from-line" /></template>

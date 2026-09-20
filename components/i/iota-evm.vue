<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg01fo99r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg01fo99r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:iota-evm" /></template>

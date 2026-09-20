<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj1pmedun.css';
import '../../css/n/nuy3iacup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mj1pmedun"/><path class="nuy3iacup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:disability-parking-bold" /></template>

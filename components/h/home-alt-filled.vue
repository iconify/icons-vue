<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvylydb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvylydb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:home-alt-filled" /></template>

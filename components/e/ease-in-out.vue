<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij8-ce7zs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ij8-ce7zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ease-in-out" /></template>

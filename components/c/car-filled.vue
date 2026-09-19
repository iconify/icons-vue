<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px0hoobzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="px0hoobzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:car-filled" /></template>

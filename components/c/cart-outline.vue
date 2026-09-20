<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgpsmabvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bgpsmabvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-outline" /></template>

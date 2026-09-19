<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2t00jb8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2t00jb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hotel-bell" /></template>

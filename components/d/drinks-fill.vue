<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nefux0p3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nefux0p3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:drinks-fill" /></template>

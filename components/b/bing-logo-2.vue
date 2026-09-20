<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phc95vc3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phc95vc3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:bing-logo-2" /></template>

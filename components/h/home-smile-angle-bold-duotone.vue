<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swf6libns.css';
import '../../css/n/nosnhobdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swf6libns"/><path class="nosnhobdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:home-smile-angle-bold-duotone" /></template>

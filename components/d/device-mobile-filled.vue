<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0d4t8bwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0d4t8bwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-mobile-filled" /></template>

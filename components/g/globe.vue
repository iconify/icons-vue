<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u41rktw1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u41rktw1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:globe" /></template>

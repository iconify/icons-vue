<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc4k0s5gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lc4k0s5gf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flight-land-fill" /></template>

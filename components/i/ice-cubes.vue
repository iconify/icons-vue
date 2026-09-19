<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvp1kxbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvp1kxbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ice-cubes" /></template>

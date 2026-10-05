<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw1_3bc7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mw1_3bc7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:chevron-right" /></template>

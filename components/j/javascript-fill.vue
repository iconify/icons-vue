<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flrk_ibxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flrk_ibxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:javascript-fill" /></template>

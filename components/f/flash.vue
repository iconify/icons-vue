<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo-2h0bcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo-2h0bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:flash" /></template>

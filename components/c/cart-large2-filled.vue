<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4r4dxvcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4r4dxvcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cart-large2-filled" /></template>

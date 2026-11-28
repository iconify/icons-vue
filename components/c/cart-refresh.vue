<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh7f7tbpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh7f7tbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cart-refresh" /></template>

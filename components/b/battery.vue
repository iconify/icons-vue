<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk-k9mswx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk-k9mswx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:battery" /></template>

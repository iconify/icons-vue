<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yphyl1bqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yphyl1bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:crown-minimalistic-broken" /></template>

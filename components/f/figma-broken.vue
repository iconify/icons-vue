<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iia-u33yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iia-u33yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:figma-broken" /></template>

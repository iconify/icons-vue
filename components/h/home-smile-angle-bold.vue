<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggmu08bpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ggmu08bpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:home-smile-angle-bold" /></template>

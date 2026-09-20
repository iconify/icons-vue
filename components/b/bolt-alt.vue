<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwf-mbcfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwf-mbcfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:bolt-alt" /></template>

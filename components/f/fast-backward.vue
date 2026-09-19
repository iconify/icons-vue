<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn_jll_0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hn_jll_0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:fast-backward" /></template>

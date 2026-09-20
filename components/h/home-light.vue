<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6or-hf8r.css';
import '../../css/u/ux5vwpivn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6or-hf8r"/><path class="ux5vwpivn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:home-light" /></template>

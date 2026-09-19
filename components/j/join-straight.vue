<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_5fgbyrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_5fgbyrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:join-straight" /></template>

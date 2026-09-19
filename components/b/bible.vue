<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yijvj917a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yijvj917a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:bible" /></template>

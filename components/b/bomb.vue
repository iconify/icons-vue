<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_yqxhbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_yqxhbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:bomb" /></template>

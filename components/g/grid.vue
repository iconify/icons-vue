<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ini8zz_bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ini8zz_bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:grid" /></template>

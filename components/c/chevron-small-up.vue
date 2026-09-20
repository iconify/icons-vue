<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr2bya.css';
import '../../css/s/so-from-10.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr2bya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:chevron-small-up" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvxm3_bax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvxm3_bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:firetv" /></template>

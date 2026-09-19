<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wet55gblz.css';
import '../../css/y/yonkb7w3v.css';
import '../../css/v/v9kz_bb3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wet55gblz"/><path class="yonkb7w3v"/><path class="v9kz_bb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:convex" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_c2798nt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_c2798nt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:folder-play" /></template>

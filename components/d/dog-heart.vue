<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2t-as2ut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2t-as2ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:dog-heart" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nobvpzbdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nobvpzbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:icon-stop-music-16" /></template>

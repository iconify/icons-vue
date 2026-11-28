<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ino_fohpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ino_fohpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cabin-heart" /></template>

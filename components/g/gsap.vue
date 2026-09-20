<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igs6o1bpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igs6o1bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:gsap" /></template>

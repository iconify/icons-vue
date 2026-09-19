<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my1rp3rmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="my1rp3rmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:arrow-up" /></template>

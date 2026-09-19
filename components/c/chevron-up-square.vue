<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj2lksehw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dj2lksehw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:chevron-up-square" /></template>

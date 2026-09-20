<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phflicz3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phflicz3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:android-line" /></template>

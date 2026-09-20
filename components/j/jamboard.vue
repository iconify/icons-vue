<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj4baj38d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj4baj38d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:jamboard" /></template>

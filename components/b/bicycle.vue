<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w355t0b1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="w355t0b1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:bicycle" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv_ezp8gy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jv_ezp8gy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:magic-wand-04" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mae22ab3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mae22ab3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:expand" /></template>

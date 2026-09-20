<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmapptb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmapptb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:glasses-fill" /></template>

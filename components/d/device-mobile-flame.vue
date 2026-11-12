<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jit5hm-5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jit5hm-5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-mobile-flame" /></template>

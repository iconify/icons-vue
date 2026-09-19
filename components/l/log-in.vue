<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwt8qti7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwt8qti7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:log-in" /></template>

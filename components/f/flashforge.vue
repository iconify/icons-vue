<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj8hq6oxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cj8hq6oxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:flashforge" /></template>

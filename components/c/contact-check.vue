<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzz0judbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzz0judbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:contact-check" /></template>

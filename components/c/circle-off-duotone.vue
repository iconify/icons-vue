<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la0tybdob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la0tybdob primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-off-duotone" /></template>

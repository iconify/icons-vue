<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvso51bws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvso51bws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:cookie-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_8h8ijtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_8h8ijtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:book-outline" /></template>

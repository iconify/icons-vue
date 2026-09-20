<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr4n1vk1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr4n1vk1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:bookmark-duotone" /></template>

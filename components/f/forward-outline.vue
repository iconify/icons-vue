<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3tiwg6bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3tiwg6bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:forward-outline" /></template>

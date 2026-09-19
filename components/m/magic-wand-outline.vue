<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhdlv3rcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhdlv3rcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:magic-wand-outline" /></template>

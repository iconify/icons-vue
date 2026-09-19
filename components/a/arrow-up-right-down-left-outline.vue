<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k13mh-w9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k13mh-w9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:arrow-up-right-down-left-outline" /></template>

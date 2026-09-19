<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qksbz5ces.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qksbz5ces"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:envelope-outline" /></template>

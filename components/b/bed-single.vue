<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voj3xbb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="voj3xbb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:bed-single" /></template>

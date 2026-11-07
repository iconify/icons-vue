<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swvwx0b5q.css';
import '../../css/p/pfluh_2pb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swvwx0b5q"/><path clip-rule="evenodd" class="pfluh_2pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:home-2-outline" /></template>

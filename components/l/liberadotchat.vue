<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1l9o0bvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1l9o0bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:liberadotchat" /></template>

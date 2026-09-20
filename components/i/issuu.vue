<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcmt7s_3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcmt7s_3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:issuu" /></template>

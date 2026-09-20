<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnqtpl8nr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnqtpl8nr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:behance-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv3hw0rzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv3hw0rzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cloud-alt-2" /></template>

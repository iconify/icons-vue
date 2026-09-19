<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh_46raup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dh_46raup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:blanket" /></template>

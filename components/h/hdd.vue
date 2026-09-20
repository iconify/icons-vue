<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqj97scze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqj97scze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:hdd" /></template>

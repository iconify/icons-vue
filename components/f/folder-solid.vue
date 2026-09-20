<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inov2jebv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inov2jebv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:folder-solid" /></template>

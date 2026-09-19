<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3kzb3mmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3kzb3mmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-ppt-outline" /></template>

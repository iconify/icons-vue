<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c63ibibyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c63ibibyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:folder-arrow-right-outline" /></template>

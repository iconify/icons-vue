<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg0cz-ynl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg0cz-ynl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:check-solid" /></template>

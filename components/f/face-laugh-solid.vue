<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqs2meyid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vqs2meyid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:face-laugh-solid" /></template>

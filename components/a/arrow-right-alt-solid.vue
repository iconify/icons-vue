<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slxx8490d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="slxx8490d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:arrow-right-alt-solid" /></template>

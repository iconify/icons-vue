<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzsoemb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gzsoemb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:folder-plus-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwzkkpb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mwzkkpb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:annotation-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcfv0ubpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcfv0ubpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:delete-row-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzj9qebqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzj9qebqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:hammer-solid" /></template>

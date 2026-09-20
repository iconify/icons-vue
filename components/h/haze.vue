<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyn0-_b9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyn0-_b9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:haze" /></template>

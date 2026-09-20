<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ziiv523bf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ziiv523bf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:khronosgroup" /></template>

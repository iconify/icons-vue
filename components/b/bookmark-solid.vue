<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy4terb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy4terb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:bookmark-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3zsrnb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i3zsrnb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:bullhorn-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwm7a-bih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwm7a-bih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:database-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxkziga4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxkziga4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:headlessui" /></template>

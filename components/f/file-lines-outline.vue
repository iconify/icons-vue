<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/meftk6b6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="meftk6b6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-lines-outline" /></template>

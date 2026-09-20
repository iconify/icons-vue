<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4plfyblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4plfyblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:airfrance" /></template>

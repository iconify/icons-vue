<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc2iix-ch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fc2iix-ch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:bullhorn" /></template>

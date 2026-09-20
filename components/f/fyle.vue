<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be1-8ab4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="be1-8ab4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:fyle" /></template>

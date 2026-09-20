<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvofh2j9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-5};
const content = `<path class="uvofh2j9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:cloud" /></template>

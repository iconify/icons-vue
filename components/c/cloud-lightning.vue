<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k788n-8wd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k788n-8wd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:cloud-lightning" /></template>

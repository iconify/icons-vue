<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt71qjbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qt71qjbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:folder-open-outline" /></template>

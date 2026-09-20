<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od6qm09ky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="od6qm09ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:iconjar" /></template>

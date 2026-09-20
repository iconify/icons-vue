<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt4zbitpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt4zbitpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ibm" /></template>

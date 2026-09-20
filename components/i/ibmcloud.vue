<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6lc-5iso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6lc-5iso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ibmcloud" /></template>

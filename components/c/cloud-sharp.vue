<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md2u8j46v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="md2u8j46v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:cloud-sharp" /></template>

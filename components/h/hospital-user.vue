<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb6b2vb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="bb6b2vb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hospital-user" /></template>

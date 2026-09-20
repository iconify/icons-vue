<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od07oia4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="od07oia4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hand-scissors-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsm7jgz4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="tsm7jgz4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:font-awesome-flag" /></template>

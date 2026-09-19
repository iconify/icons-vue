<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzzkz4bes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="bzzkz4bes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:h-square" /></template>

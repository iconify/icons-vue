<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klbmyhl8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="klbmyhl8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:indent-increase-20" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukhaiwb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ukhaiwb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:anchr-dark" /></template>

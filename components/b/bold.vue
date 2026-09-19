<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xamjfw8ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="xamjfw8ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:bold" /></template>

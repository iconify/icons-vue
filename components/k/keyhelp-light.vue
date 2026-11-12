<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah50ngbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ah50ngbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:keyhelp-light" /></template>

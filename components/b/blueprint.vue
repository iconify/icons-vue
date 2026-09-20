<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsgjlwb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsgjlwb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:blueprint" /></template>

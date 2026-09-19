<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzlt8abim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hzlt8abim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:appwrite-wordmark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il0amvbum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="il0amvbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:admin-1" /></template>

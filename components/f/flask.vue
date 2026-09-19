<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewnc5nb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ewnc5nb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:flask" /></template>

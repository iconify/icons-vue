<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quqxhm_8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":396,"height":512};
const content = `<path class="quqxhm_8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:haml" /></template>

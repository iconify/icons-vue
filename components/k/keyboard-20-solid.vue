<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad106q2ot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ad106q2ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:keyboard-20-solid" /></template>

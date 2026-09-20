<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm1ss5uze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nm1ss5uze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:face-smile-plus-16-solid" /></template>

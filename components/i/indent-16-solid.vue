<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs49-jbes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xs49-jbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:indent-16-solid" /></template>

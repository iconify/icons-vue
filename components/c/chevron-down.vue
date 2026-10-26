<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt3hhu20u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zt3hhu20u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:chevron-down" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isqhvabpe.css';
import '../../css/a/a13mabcgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="isqhvabpe"/><path class="a13mabcgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:coupling-48-bold" /></template>

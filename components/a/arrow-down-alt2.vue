<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejfwa9bbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ejfwa9bbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:arrow-down-alt2" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5z7xj-nu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s5z7xj-nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:at" /></template>

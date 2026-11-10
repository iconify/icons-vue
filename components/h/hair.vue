<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du9gf8b7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="du9gf8b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:hair" /></template>

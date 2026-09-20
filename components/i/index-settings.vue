<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo6jjhb5p.css';
import '../../css/e/eroa1ibmd.css';
import '../../css/e/ebh6vui7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lo6jjhb5p"/><path class="eroa1ibmd"/><path class="ebh6vui7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:index-settings" /></template>

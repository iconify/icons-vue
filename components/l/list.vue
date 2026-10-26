<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mazpctb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mazpctb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:list" /></template>

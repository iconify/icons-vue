<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll4-n--4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ll4-n--4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:eye-off" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_y62ub1b.css';
import '../../css/g/go0ezbdtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x_y62ub1b"/><path class="go0ezbdtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:eye-off-48" /></template>

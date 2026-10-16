<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb9x9-c_l.css';
import '../../css/x/xv2q6jbej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mb9x9-c_l"/><path class="xv2q6jbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-star-48" /></template>

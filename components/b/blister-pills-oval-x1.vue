<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqf4v9bys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lqf4v9bys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blister-pills-oval-x1" /></template>

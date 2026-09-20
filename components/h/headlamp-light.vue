<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezzg8ab2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ezzg8ab2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:headlamp-light" /></template>

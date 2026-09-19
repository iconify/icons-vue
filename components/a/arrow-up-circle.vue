<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tny2aw3uc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tny2aw3uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:arrow-up-circle" /></template>

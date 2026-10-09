<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke_77zjpb.css';
import '../../css/b/bblukg9bh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ke_77zjpb"/><path class="bblukg9bh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:eye-off-20-bold" /></template>

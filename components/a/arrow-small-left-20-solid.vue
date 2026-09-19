<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsn_v_jiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jsn_v_jiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-small-left-20-solid" /></template>

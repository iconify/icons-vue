<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhsep8akp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jhsep8akp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:72x-outline" /></template>

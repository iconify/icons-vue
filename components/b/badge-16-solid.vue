<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjjbun7en.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xjjbun7en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:badge-16-solid" /></template>

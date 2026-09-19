<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwv-pjobw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gwv-pjobw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:exclamation-triangle-16-solid" /></template>

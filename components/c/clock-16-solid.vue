<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyq2iubmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kyq2iubmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:clock-16-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv_5ogdeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qv_5ogdeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:globe-europe-africa-16-solid" /></template>

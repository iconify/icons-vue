<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf_wfvb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lf_wfvb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:atlassian" /></template>

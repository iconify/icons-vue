<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qokpr-bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qokpr-bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:download-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3mh3qbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":754};
const content = `<path class="s3mh3qbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:l" /></template>

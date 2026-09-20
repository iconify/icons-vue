<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8en0-mhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q8en0-mhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jira-dark" /></template>

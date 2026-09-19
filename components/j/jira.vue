<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsvu0-b5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="tsvu0-b5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:jira" /></template>

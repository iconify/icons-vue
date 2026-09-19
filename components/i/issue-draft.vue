<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5gnv6y7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n5gnv6y7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:issue-draft" /></template>

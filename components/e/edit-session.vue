<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbcjab_aq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lbcjab_aq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:edit-session" /></template>

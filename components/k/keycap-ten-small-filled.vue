<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm0tryqzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="dm0tryqzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-ten-small-filled" /></template>

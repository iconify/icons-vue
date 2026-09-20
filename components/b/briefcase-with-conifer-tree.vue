<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srlffk1ha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="srlffk1ha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:briefcase-with-conifer-tree" /></template>

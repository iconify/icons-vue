<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca_58wb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ca_58wb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:calendar" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwuztabgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pwuztabgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:geo-dots" /></template>

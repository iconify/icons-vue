<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhpwkq3jg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uhpwkq3jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-directory-open-fill-16" /></template>

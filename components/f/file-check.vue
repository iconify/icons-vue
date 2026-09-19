<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7rnv2w-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j7rnv2w-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:file-check" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkw81ac-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dkw81ac-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:boolean-exclude" /></template>

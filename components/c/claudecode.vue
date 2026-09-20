<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au73r9tay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="au73r9tay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:claudecode" /></template>

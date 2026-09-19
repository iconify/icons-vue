<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db_g-1b0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="db_g-1b0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:code-commit" /></template>

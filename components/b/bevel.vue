<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj95kiqzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bj95kiqzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:bevel" /></template>

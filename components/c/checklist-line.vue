<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-pkddbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-pkddbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:checklist-line" /></template>

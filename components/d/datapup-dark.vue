<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0hhnivpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j0hhnivpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:datapup-dark" /></template>

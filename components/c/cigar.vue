<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arjkkbgup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="arjkkbgup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cigar" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvj-_sb0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="lvj-_sb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:firefox" /></template>

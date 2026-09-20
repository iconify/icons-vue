<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odlgx4b7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="odlgx4b7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:circle-16" /></template>

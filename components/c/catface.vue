<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn8j0-frr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gn8j0-frr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:catface" /></template>

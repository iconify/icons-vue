<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e64surbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":897,"height":1024};
const content = `<path class="e64surbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:invoice" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el31n6bjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="el31n6bjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:dentist-15" /></template>

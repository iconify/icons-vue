<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5jew8byw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o5jew8byw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:bar-15" /></template>

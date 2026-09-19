<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf9sv6wma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tf9sv6wma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:elgg" /></template>

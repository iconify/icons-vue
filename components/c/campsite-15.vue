<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkp9x86_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pkp9x86_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:campsite-15" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntk51_c5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":896};
const content = `<path class="ntk51_c5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:leechprotect" /></template>

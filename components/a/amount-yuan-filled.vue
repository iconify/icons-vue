<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc0g5vt9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bc0g5vt9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:amount-yuan-filled" /></template>

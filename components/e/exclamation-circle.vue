<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfh1ikz9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bfh1ikz9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:exclamation-circle" /></template>

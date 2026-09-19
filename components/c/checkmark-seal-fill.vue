<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi1la0bde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="xi1la0bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:checkmark-seal-fill" /></template>

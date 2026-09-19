<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxw1mmmpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1025};
const content = `<path class="oxw1mmmpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:hockey" /></template>

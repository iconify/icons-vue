<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy_cr8baz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xy_cr8baz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:logo-protools" /></template>

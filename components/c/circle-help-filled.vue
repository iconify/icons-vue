<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5tc0hb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="m5tc0hb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:circle-help-filled" /></template>

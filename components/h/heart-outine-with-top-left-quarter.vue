<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv-ticcvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dv-ticcvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:heart-outine-with-top-left-quarter" /></template>

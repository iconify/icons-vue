<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owt28_bhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="owt28_bhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:battery" /></template>

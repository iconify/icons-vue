<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br7nqpp0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="br7nqpp0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cairn-beside-trail-blazes-up" /></template>

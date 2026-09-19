<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r09i3hofv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r09i3hofv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:dice-3-fill" /></template>

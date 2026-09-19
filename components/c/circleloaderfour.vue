<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud46_zbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":1024};
const content = `<path class="ud46_zbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circleloaderfour" /></template>

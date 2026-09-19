<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bocfkcb9c.css';
import '../../css/p/pi8mxsaiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bocfkcb9c"/><path clip-rule="evenodd" class="pi8mxsaiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:currency-dollar-16-solid" /></template>

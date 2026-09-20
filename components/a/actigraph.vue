<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el94-sgza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el94-sgza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:actigraph" /></template>

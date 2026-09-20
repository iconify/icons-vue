<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm58fobcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pm58fobcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:highway-rest-area" /></template>

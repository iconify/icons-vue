<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4z7izb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n4z7izb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:bicycle-15" /></template>

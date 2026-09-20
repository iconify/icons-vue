<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0w312bli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q0w312bli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:barbed-hook" /></template>

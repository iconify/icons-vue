<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upuqfew_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="upuqfew_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:candlepin-with-ball" /></template>

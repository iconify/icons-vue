<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azu17zcxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="azu17zcxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:connections" /></template>

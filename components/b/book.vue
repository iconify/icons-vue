<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3oc6nbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j3oc6nbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:book" /></template>

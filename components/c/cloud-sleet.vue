<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovop27obc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ovop27obc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:cloud-sleet" /></template>

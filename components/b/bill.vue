<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl010k52n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vl010k52n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:bill" /></template>

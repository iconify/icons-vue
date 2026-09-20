<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g37t12bqh.css';
import '../../css/h/hbi26vbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g37t12bqh"/><path class="hbi26vbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:boolean-on-16" /></template>

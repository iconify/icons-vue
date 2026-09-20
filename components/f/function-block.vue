<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gldf50b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gldf50b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:function-block" /></template>

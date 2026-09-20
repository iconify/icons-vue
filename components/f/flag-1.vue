<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4d10v-zk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="j4d10v-zk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:flag-1" /></template>

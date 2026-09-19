<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf5j8vb-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="qf5j8vb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hospital-user" /></template>

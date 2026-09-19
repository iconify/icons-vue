<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8t4m96uj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":435,"height":512};
const content = `<path class="k8t4m96uj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:libuv" /></template>

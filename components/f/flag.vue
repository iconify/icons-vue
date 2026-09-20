<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrb-vva6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wrb-vva6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:flag" /></template>

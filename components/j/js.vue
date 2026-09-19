<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcdrcvb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xcdrcvb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:js" /></template>

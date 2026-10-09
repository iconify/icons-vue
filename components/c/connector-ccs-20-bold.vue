<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5i-rfb6g.css';
import '../../css/p/pcvcreaar.css';
import '../../css/c/cotzlwrvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e5i-rfb6g"/><path class="pcvcreaar"/><path class="cotzlwrvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:connector-ccs-20-bold" /></template>

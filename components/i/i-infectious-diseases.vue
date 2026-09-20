<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg9xpcbkq.css';
import '../../css/u/u-l7qbbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="lg9xpcbkq"/><path class="u-l7qbbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-infectious-diseases" /></template>

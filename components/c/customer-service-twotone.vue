<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phr3r27xz.css';
import '../../css/z/z9r3_1dmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="phr3r27xz"/><path class="z9r3_1dmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:customer-service-twotone" /></template>

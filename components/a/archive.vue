<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri-d8bcfx.css';
import '../../css/b/b7j_n5anm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ri-d8bcfx"/><path class="b7j_n5anm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:archive" /></template>

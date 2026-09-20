<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx-j32p0d.css';
import '../../css/a/ad3korw9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jx-j32p0d"/><path class="ad3korw9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-immunizations" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eli7y2biq.css';
import '../../css/p/pb5i8-bvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eli7y2biq"/><path class="pb5i8-bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:fire-hydrant-underground" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydbk_ybiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ydbk_ybiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:edit-circle-solid" /></template>

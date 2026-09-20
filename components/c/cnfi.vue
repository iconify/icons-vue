<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zid-e6bvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zid-e6bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cnfi" /></template>

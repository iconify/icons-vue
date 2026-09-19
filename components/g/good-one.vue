<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxmk_0bvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zxmk_0bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:good-one" /></template>

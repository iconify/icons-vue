<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk6b_0bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zk6b_0bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:layout-header-columns" /></template>

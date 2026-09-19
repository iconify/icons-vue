<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl9ltt5qx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zl9ltt5qx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:bars-ascending-align-left-arrow-up" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns_wucbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ns_wucbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bladder" /></template>

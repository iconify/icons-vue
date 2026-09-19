<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvvo5resr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="mvvo5resr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:closetab" /></template>

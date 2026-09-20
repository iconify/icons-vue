<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-o5xobzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-o5xobzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:ai" /></template>

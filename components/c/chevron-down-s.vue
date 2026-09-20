<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9_he8bvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9_he8bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chevron-down-s" /></template>

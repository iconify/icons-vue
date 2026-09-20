<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmavll4ox.css';
import '../../css/z/zj49idy7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmavll4ox"/><path class="zj49idy7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:clock-24" /></template>

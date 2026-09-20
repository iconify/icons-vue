<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh8cc2nme.css';
import '../../css/z/z6m2ovbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kh8cc2nme"/><path class="z6m2ovbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:alist" /></template>

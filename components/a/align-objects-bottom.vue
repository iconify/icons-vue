<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhkgv3b3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhkgv3b3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:align-objects-bottom" /></template>

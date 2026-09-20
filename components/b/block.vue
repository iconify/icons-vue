<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ellkj-bdc.css';
import '../../css/q/qhrkrwb9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ellkj-bdc"/><path class="qhrkrwb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:block" /></template>

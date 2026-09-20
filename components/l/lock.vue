<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_-jdccjs.css';
import '../../css/s/sg9i7d4jt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_-jdccjs"/><rect class="sg9i7d4jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:lock" /></template>

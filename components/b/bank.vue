<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-3f8hxqz.css';
import '../../css/c/cdssnbbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-3f8hxqz"/><path class="cdssnbbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bank" /></template>

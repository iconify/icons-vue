<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg9xrn2wd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg9xrn2wd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:eject-line" /></template>

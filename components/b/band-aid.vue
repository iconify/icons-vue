<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_66s4b0b.css';
import '../../css/d/dwwqc9d1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_66s4b0b"/><path class="dwwqc9d1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:band-aid" /></template>

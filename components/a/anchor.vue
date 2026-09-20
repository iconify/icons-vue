<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex2-leshc.css';
import '../../css/k/kg2uyccfb.css';
import '../../css/y/y1nytpm2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex2-leshc"/><path class="kg2uyccfb"/><path class="y1nytpm2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:anchor" /></template>

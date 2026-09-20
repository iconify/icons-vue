<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1-dclb0l.css';
import '../../css/n/nuuqustnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="t1-dclb0l"/><path class="nuuqustnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:data-search-filled" /></template>

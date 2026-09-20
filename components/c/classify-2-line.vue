<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbvt85_wv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbvt85_wv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:classify-2-line" /></template>

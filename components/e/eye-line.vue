<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfoobn32z.css';
import '../../css/m/mzwwu8c7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfoobn32z"/><path class="mzwwu8c7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:eye-line" /></template>

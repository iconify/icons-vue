<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzfm5-qmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzfm5-qmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cardano-ada-fill" /></template>

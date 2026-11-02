<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5dn7oa5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5dn7oa5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cardano-ada-line" /></template>

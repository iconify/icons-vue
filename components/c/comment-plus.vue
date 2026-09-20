<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzowd3bfo.css';
import '../../css/k/k_mslbcbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzowd3bfo"/><path class="k_mslbcbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:comment-plus" /></template>

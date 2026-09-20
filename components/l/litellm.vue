<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1_8iubmh.css';
import '../../css/c/cl2ahfl2g.css';
import '../../css/n/nc-y7w9wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n1_8iubmh"/><path class="cl2ahfl2g"/><path class="nc-y7w9wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:litellm" /></template>

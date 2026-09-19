<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njkt2bj_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="njkt2bj_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:edit-large" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4n1kbb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-6,"top":-2};
const content = `<path class="l4n1kbb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:hourglass-f" /></template>

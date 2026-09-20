<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc8ov__gv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nc8ov__gv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:grid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsr0t4_oa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsr0t4_oa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:crunchyrol" /></template>

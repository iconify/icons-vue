<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnep0m7rs.css';
import '../../css/z/zar1cn4so.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnep0m7rs"/><path class="zar1cn4so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-up-left-circle" /></template>

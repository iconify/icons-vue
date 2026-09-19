<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az_vxbc1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="az_vxbc1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:list-bullet-indent" /></template>

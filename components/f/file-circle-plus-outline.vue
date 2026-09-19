<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmg372boc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmg372boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-circle-plus-outline" /></template>

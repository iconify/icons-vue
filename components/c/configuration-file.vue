<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xatnruabq.css';
import '../../css/y/ynuha5bfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xatnruabq"/><path class="ynuha5bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:configuration-file" /></template>

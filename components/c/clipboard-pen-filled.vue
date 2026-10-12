<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nauphjpxp.css';
import '../../css/g/grxjc5bmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nauphjpxp"/><path clip-rule="evenodd" class="grxjc5bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:clipboard-pen-filled" /></template>

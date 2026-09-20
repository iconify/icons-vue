<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifde2vb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifde2vb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:horizontal-down-left-main" /></template>

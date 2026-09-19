<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1f-u5b-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1f-u5b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:data-scientist-outlined" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx_lz50_l.css';
import '../../css/w/wih7av0dv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nx_lz50_l"/><path class="wih7av0dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:file-remove-outline" /></template>

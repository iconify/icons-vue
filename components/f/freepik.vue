<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz9z31bkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz9z31bkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:freepik" /></template>

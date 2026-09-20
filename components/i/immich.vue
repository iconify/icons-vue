<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw7f53skv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw7f53skv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:immich" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjut7gbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjut7gbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:leaf-three" /></template>

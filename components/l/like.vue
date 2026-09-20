<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyp_tob4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zyp_tob4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:like" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk-c65bsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bk-c65bsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:buildings" /></template>

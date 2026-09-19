<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig0hw9b-i.css';
import '../../css/j/jjz706w_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig0hw9b-i"/><path class="jjz706w_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:cloud-translation-api" /></template>

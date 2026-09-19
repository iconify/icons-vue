<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjb5d5f1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjb5d5f1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:cool" /></template>

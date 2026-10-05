<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igo2_5qvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igo2_5qvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:folder" /></template>

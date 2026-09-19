<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9su1ekzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9su1ekzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:briefcase" /></template>

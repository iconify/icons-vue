<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl47__mjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pl47__mjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bug-plus" /></template>

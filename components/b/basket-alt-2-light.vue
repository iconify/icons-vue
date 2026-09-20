<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awfpctb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awfpctb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:basket-alt-2-light" /></template>

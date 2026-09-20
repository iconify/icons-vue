<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5_mrgt4f.css';
import '../../css/f/f86ggwbgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5_mrgt4f"/><path class="f86ggwbgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bsgg" /></template>

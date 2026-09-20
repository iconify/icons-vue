<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8dv1dyig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8dv1dyig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:chevron-up-expressive" /></template>

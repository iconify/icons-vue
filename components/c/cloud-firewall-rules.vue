<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odihjmfut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odihjmfut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:cloud-firewall-rules" /></template>

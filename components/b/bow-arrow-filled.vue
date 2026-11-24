<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8l8tibar.css';
import '../../css/s/s_xabeb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8l8tibar"/><path class="s_xabeb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bow-arrow-filled" /></template>

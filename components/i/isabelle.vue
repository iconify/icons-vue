<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_k_gkv_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t_k_gkv_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:isabelle" /></template>

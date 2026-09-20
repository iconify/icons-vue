<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub0hiubzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ub0hiubzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:documents-minimalistic-outline" /></template>

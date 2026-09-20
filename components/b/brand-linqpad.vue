<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_8a8kt0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_8a8kt0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-linqpad" /></template>

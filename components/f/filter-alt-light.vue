<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-zzptoit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-zzptoit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:filter-alt-light" /></template>

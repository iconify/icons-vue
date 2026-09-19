<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um_pv-brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="um_pv-brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:folder-open" /></template>

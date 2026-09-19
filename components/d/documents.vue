<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-1fm9-zs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-1fm9-zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:documents" /></template>

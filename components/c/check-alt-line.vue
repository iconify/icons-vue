<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar4e_gbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar4e_gbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:check-alt-line" /></template>

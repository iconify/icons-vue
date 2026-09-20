<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcaoaob4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcaoaob4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-fill" /></template>

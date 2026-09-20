<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwbvoi8sn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwbvoi8sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:left-down-line" /></template>

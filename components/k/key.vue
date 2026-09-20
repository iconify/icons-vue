<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4vm18b5j.css';
import '../../css/b/bosvvnbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4vm18b5j"/><path clip-rule="evenodd" class="bosvvnbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:key" /></template>

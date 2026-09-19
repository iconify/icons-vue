<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aztr-g88x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aztr-g88x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cloud-lightning" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpnj8obih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpnj8obih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-join" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1nxg7bnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1nxg7bnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cloud-spark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_rdtob6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e_rdtob6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:crown-2-filled" /></template>

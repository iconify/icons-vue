<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjls-dbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pjls-dbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-1-fill" /></template>

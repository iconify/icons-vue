<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsb7o42fp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsb7o42fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:italic" /></template>

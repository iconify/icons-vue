<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opei0frxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opei0frxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:arrow-up-thick" /></template>

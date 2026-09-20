<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubvnbacyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubvnbacyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-google" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojr94bcww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojr94bcww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:airpods-r" /></template>

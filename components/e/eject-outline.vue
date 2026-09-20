<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqldz6btv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqldz6btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:eject-outline" /></template>

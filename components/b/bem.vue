<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md1ywzv1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="md1ywzv1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bem" /></template>

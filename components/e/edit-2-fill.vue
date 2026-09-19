<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv1rtebcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv1rtebcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:edit-2-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr7qlh-st.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fr7qlh-st"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:cos" /></template>

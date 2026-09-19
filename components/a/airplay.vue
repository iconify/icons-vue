<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vagjwfb3n.css';
import '../../css/b/ba21eebdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vagjwfb3n"/><path class="ba21eebdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:airplay" /></template>

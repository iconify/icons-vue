<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g41g3cfca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g41g3cfca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:fire-solid" /></template>

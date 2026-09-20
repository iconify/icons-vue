<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9r-36cdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9r-36cdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-autofit-content-filled" /></template>

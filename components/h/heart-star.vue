<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h908iiygx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h908iiygx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:heart-star" /></template>

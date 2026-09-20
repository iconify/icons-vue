<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iduzk8jau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iduzk8jau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-bottombar" /></template>

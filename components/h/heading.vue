<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zeruo7bxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zeruo7bxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:heading" /></template>

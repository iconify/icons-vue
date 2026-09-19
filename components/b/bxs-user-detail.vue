<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twkmy8jve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twkmy8jve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-user-detail" /></template>

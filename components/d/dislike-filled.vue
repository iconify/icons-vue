<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elx1ufbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="elx1ufbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dislike-filled" /></template>

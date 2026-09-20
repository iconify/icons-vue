<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7_0c7bxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7_0c7bxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:eye-dotted" /></template>

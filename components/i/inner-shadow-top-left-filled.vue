<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntopc1bgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntopc1bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:inner-shadow-top-left-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3m9doboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3m9doboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:inner-shadow-top-right-filled" /></template>

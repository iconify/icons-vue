<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okyr0-bih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okyr0-bih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-half-2" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obky_6v6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obky_6v6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:external-link-off" /></template>

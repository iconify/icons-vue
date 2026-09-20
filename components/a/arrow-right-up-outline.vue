<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cib8es_1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cib8es_1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-right-up-outline" /></template>

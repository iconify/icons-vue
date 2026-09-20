<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utyq8365n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utyq8365n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-patreon" /></template>

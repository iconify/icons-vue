<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crit0-b8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crit0-b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-metabrainz" /></template>

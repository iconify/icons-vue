<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-5e8sbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-5e8sbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-google-podcasts" /></template>

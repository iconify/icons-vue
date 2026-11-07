<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_sy2m0fq.css';
import '../../css/v/vyk6wnbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_sy2m0fq"/><path clip-rule="evenodd" class="vyk6wnbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifier-slash-outline" /></template>

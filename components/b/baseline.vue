<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bog__x_pt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bog__x_pt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:baseline" /></template>

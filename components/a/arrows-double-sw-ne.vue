<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwkvqcc-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwkvqcc-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrows-double-sw-ne" /></template>

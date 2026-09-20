<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc_63cp2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lc_63cp2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:arrow-retry-duotone" /></template>

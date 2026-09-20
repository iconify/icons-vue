<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljkyuv24o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljkyuv24o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-big-up-sharp-fill" /></template>

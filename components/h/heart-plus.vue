<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyk017emc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyk017emc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:heart-plus" /></template>

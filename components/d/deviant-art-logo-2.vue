<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k14xmiymw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k14xmiymw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:deviant-art-logo-2" /></template>

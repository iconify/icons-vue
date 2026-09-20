<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3lca2bsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3lca2bsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-up-right-box-sharp-fill" /></template>

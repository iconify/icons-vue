<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si-mzjgyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="si-mzjgyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-caret-down-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgytc7ilk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgytc7ilk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-down-left-box-sharp" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxa_h81tv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxa_h81tv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:information-circle" /></template>

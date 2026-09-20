<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv55wflry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hv55wflry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:add-circle-fill" /></template>

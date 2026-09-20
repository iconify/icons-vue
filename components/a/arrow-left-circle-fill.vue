<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk2674f5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uk2674f5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:arrow-left-circle-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juvra6bcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juvra6bcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:direction-button-3-bold" /></template>

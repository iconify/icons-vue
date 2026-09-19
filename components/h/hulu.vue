<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c65j88bqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c65j88bqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:hulu" /></template>

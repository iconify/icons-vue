<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jku9oud5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jku9oud5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:mail-line" /></template>

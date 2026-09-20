<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3mjm7bvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3mjm7bvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:arrow-left-square-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1kfdbb0u.css';
import '../../css/l/lieqa6bpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="q1kfdbb0u"/><path class="lieqa6bpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:img-fill" /></template>

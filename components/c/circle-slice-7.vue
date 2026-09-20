<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl9i0ubuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kl9i0ubuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:circle-slice-7" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_ecgq4-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_ecgq4-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:forbidden-phone-off" /></template>

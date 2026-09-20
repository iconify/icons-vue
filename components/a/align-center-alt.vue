<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp_dzibvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp_dzibvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:align-center-alt" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnop98bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnop98bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:device-database-encryption-1" /></template>

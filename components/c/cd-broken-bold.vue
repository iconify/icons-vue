<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8a918fho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8a918fho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:cd-broken-bold" /></template>

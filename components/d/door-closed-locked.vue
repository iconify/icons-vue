<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0m4y9b-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0m4y9b-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:door-closed-locked" /></template>

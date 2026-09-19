<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu_l0pbck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu_l0pbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:garden" /></template>

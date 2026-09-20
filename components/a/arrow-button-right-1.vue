<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu_n3ebem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu_n3ebem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:arrow-button-right-1" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl4m9cb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kl4m9cb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:brandfetch" /></template>

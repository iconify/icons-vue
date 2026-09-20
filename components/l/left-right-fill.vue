<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk1g1aczw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk1g1aczw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:left-right-fill" /></template>

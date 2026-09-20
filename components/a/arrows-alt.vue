<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g35dlbbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g35dlbbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:arrows-alt" /></template>

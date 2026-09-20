<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk3ve9yfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kk3ve9yfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:cancel-photo-line" /></template>

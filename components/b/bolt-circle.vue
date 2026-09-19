<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phur5pbvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phur5pbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:bolt-circle" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf-tyyb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jf-tyyb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bolt-off" /></template>

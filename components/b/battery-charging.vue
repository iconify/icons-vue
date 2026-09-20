<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft_j2-bbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft_j2-bbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:battery-charging" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p48dyi2lt.css';
import '../../css/e/emos5l7br.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p48dyi2lt"/><path class="emos5l7br"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:check-square" /></template>

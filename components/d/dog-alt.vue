<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-i1pqbhz.css';
import '../../css/e/ecv-qkvdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-i1pqbhz"/><path class="ecv-qkvdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dog-alt" /></template>

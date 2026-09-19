<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohwe0piix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohwe0piix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:centris-three" /></template>

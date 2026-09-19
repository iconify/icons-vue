<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6pye4bhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6pye4bhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:doctor-02" /></template>
